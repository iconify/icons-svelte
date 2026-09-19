<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9b2swbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="q9b2swbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:toilet-paper" {...props}></Icon>
