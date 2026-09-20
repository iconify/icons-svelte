<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr5ftn4xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr5ftn4xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:skateboard-off" {...props}></Icon>
