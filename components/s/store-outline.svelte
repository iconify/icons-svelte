<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr8qrx7dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wr8qrx7dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:store-outline" {...props}></Icon>
