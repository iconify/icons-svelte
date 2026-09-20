<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3q5q3bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c3q5q3bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:termix-dark" {...props}></Icon>
