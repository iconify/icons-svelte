<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap69csexs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap69csexs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:umbrella-filled" {...props}></Icon>
