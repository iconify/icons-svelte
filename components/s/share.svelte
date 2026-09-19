<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlsu96b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tlsu96b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:share" {...props}></Icon>
