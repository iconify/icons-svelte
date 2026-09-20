<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7oblxb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m7oblxb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:seaplane-descending" {...props}></Icon>
