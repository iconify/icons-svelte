<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrvyqicgf.css';
import '../../css/h/hxwgvtb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hrvyqicgf"/><path class="hxwgvtb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signature-20" {...props}></Icon>
