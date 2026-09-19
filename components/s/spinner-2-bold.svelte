<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgbds-orp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qgbds-orp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:spinner-2-bold" {...props}></Icon>
