<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al7f0nbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="al7f0nbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:thumb-down" {...props}></Icon>
