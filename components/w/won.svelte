<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghzw70bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ghzw70bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:won" {...props}></Icon>
