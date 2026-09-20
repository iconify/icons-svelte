<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5-mv2ddo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f5-mv2ddo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-with-sweat-in-circle" {...props}></Icon>
