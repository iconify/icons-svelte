<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot1fkivfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="ot1fkivfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:stroller" {...props}></Icon>
