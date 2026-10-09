<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huersmbrs.css';
import '../../css/y/ydb89tdze.css';
import '../../css/c/cw9woomrs.css';
import '../../css/r/rx31uvbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="huersmbrs"/><path class="ydb89tdze"/><path class="cw9woomrs"/><path class="rx31uvbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:snowflake-20-bold" {...props}></Icon>
