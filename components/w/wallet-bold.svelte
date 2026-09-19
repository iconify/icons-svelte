<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5dlufbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="s5dlufbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wallet-bold" {...props}></Icon>
