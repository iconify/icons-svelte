<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhgt1i-cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uhgt1i-cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:square-stroked-15" {...props}></Icon>
