<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd9beubnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dd9beubnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:street-cabinet" {...props}></Icon>
