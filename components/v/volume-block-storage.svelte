<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqix6e-9e.css';
import '../../css/r/rauwxcb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qqix6e-9e"/><path class="rauwxcb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-block-storage" {...props}></Icon>
