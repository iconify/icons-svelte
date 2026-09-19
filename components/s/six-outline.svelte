<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9c3jne9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="w9c3jne9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:six-outline" {...props}></Icon>
