<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg01lhbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jg01lhbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trowel" {...props}></Icon>
