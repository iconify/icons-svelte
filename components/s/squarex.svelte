<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhnw2lf4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="dhnw2lf4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarex" {...props}></Icon>
