<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqhqefpkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hqhqefpkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tired-bold" {...props}></Icon>
