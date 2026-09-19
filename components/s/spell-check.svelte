<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-29oacxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j-29oacxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:spell-check" {...props}></Icon>
