<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwkkckaky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wwkkckaky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:spinner-2" {...props}></Icon>
