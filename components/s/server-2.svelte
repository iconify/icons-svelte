<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3lybfbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3lybfbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:server-2" {...props}></Icon>
