<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-8kcn42z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="t-8kcn42z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:u-outline" {...props}></Icon>
