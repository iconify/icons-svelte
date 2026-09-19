<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6x5z1bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l6x5z1bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tablet-outline" {...props}></Icon>
