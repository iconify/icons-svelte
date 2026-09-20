<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjehtdb3z.css';
import '../../css/y/ys0-a9buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mjehtdb3z"/><path class="ys0-a9buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:wechat-logo" {...props}></Icon>
