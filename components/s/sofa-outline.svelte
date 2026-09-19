<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg8h_74nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yg8h_74nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sofa-outline" {...props}></Icon>
