<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asx97pbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="asx97pbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:x-outline" {...props}></Icon>
