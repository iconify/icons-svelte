<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh0q0mbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="fh0q0mbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:screen-dub" {...props}></Icon>
