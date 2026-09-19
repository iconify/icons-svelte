<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wye1bdb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wye1bdb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wifi-25-outline" {...props}></Icon>
