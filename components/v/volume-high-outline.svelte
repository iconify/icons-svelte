<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfgra4b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jfgra4b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:volume-high-outline" {...props}></Icon>
