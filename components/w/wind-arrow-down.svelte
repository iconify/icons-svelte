<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmc80rbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmc80rbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wind-arrow-down" {...props}></Icon>
