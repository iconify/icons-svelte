<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8b4sjb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="q8b4sjb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:text" {...props}></Icon>
