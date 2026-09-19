<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6ad0f7ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h6ad0f7ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sparkle-outline" {...props}></Icon>
