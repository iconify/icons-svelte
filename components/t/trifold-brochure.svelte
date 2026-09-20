<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjaturbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zjaturbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:trifold-brochure" {...props}></Icon>
