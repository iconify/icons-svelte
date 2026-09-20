<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq7b1j2cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vq7b1j2cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:stupa" {...props}></Icon>
