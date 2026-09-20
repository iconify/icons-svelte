<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrbp2tvgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrbp2tvgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-arrow-up-filled" {...props}></Icon>
