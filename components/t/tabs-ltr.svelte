<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_xui1bqs.css';
import '../../css/u/u8q_ug4pj.css';
import '../../css/e/e6sjhzbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a_xui1bqs"/><circle class="u8q_ug4pj"/><circle class="e6sjhzbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:tabs-ltr" {...props}></Icon>
