<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh2z7k8ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fh2z7k8ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:van-outline" {...props}></Icon>
