<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyn9yi1sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yyn9yi1sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:squircle-outline" {...props}></Icon>
