<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc0y6abmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fc0y6abmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:transfer" {...props}></Icon>
