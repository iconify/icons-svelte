<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk9-heb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tk9-heb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:target" {...props}></Icon>
