<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzpg0f4dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mzpg0f4dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tennis-ball-outline" {...props}></Icon>
