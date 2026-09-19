<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0iqh-7od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n0iqh-7od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:screenoptions" {...props}></Icon>
