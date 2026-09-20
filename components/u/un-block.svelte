<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do5d53btf.css';
import '../../css/j/j6h5hmb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="do5d53btf"/><path class="j6h5hmb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:un-block" {...props}></Icon>
