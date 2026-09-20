<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcnnylysu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jcnnylysu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:secrover-light" {...props}></Icon>
