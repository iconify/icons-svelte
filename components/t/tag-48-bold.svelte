<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw5t0sbxt.css';
import '../../css/h/hlbfg1dop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zw5t0sbxt"/><path class="hlbfg1dop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tag-48-bold" {...props}></Icon>
