<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im5r2tbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="im5r2tbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:zoom-in" {...props}></Icon>
