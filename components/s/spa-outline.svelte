<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8px1im5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y8px1im5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:spa-outline" {...props}></Icon>
