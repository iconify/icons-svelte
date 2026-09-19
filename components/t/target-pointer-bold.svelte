<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkhkx8d9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pkhkx8d9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:target-pointer-bold" {...props}></Icon>
