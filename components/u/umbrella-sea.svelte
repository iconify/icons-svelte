<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev2x8s2oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="ev2x8s2oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:umbrella-sea" {...props}></Icon>
