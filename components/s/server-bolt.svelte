<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0lg2ebmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0lg2ebmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:server-bolt" {...props}></Icon>
