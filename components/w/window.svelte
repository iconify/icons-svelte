<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whl0o8ody.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="whl0o8ody"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:window" {...props}></Icon>
