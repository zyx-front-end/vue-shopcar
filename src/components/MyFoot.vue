<template>
    <div>
        <div class="my-footer">
            <div class="custom-control custom-checkbox">
                <input type="checkbox" class="form-check-input" id="footerCheckbox">
                <label for="footerCheckbox" class="custom-control-label">
                    全选
                </label>
            </div>
            <!-- 合计 -->
            <div>
                <span>合计</span>
                <span class="price">￥0</span>
            </div>
            <!-- 结算 -->
            <button type="button" class="footer-btn btn btn-primary">结算(0)</button>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="less" scoped>
.footer-btn{
    
}
</style>