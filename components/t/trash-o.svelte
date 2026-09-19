<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_30unbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1536};
const content = `<path class="t_30unbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:trash-o" {...props}></Icon>
