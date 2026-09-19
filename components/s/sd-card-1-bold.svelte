<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_kk4nbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h_kk4nbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sd-card-1-bold" {...props}></Icon>
