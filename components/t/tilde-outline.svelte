<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eald3mbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="eald3mbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tilde-outline" {...props}></Icon>
