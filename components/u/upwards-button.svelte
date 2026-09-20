<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doj8pis9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="doj8pis9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:upwards-button" {...props}></Icon>
