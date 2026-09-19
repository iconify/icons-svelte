<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnt5_6bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hnt5_6bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sleetlet-outline" {...props}></Icon>
