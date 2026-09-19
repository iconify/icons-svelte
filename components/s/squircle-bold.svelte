<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8uot5bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a8uot5bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:squircle-bold" {...props}></Icon>
