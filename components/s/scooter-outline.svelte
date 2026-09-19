<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk_dfeb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bk_dfeb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:scooter-outline" {...props}></Icon>
