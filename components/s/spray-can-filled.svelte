<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us-3nabvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us-3nabvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:spray-can-filled" {...props}></Icon>
