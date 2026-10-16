<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx_kaouwn.css';
import '../../css/v/vd-f58bld.css';
import '../../css/w/wqm03x8_d.css';
import '../../css/w/w6rqdqpvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mx_kaouwn"/><path class="vd-f58bld"/><path class="wqm03x8_d"/><path class="w6rqdqpvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sunshine" {...props}></Icon>
