<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc61z9lrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kc61z9lrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wrench-bold" {...props}></Icon>
