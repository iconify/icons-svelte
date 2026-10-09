<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj-8ynsln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gj-8ynsln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-off-20" {...props}></Icon>
