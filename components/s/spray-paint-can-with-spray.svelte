<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v750lsb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v750lsb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spray-paint-can-with-spray" {...props}></Icon>
