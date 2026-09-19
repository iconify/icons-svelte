<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7d8vrbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r7d8vrbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:supercollider" {...props}></Icon>
