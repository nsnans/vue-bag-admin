<template>
    <button class="button" style="vertical-align:middle"><span>Download</span></button>
</template>
<style lang="less" scoped>
.button {
    display: inline-block;
    border-radius: 7px;
    border: none;
    background: #1875FF;
    color: white;
    font-family: inherit;
    text-align: center;
    font-size: 13px;
    box-shadow: 0px 14px 56px -11px #1875FF;
    width: 15em;
    padding: 1em;
    transition: all 0.4s;
    cursor: pointer;
}

.button span {
    cursor: pointer;
    display: inline-block;
    position: relative;
    transition: 0.4s;
}

.button span:after {
    content: 'for free';
    position: absolute;
    opacity: 0;
    top: 0;
    right: -20px;
    transition: 0.7s;
}

.button:hover span {
    padding-right: 3.55em;
}

.button:hover span:after {
    opacity: 4;
    right: 0;
}
</style>
