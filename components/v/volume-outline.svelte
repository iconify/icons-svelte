<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1-nasbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="v1-nasbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:volume-outline" {...props}></Icon>
