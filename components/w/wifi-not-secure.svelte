<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxs02k2xl.css';
import '../../css/c/c681w5y_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qxs02k2xl"/><path class="c681w5y_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wifi-not-secure" {...props}></Icon>
