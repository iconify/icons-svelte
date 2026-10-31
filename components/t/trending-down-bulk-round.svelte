<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3m13panc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3m13panc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trending-down-bulk-round" {...props}></Icon>
