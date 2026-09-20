<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9lp3i2ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w9lp3i2ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:theatre" {...props}></Icon>
