<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4uk9ab4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="h4uk9ab4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:signal-3" {...props}></Icon>
