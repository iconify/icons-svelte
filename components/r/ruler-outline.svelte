<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kghq_fn3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kghq_fn3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ruler-outline" {...props}></Icon>
