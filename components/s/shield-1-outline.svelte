<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz6gfd7vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nz6gfd7vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shield-1-outline" {...props}></Icon>
