<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc9qv4tax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rc9qv4tax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:triangle-outline" {...props}></Icon>
