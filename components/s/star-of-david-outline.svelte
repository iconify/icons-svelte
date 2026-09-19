<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq9y3hb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="lq9y3hb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-of-david-outline" {...props}></Icon>
