<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kppf60czi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kppf60czi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:toggle-1-outline" {...props}></Icon>
