<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkan5c65j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gkan5c65j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tablet" {...props}></Icon>
