<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5zr8ubgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5zr8ubgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tableau-light" {...props}></Icon>
