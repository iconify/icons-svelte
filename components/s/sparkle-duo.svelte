<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsvy08b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="hsvy08b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sparkle-duo" {...props}></Icon>
