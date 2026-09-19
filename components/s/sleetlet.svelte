<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3qtumeeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="n3qtumeeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sleetlet" {...props}></Icon>
