<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnn7sfq2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nnn7sfq2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shovel-outline" {...props}></Icon>
