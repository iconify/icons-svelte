<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gshz9i_sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gshz9i_sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:y-outline" {...props}></Icon>
