<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv61ubcew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="uv61ubcew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:store-break-outline" {...props}></Icon>
