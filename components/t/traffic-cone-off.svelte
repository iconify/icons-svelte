<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqhi3t3gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqhi3t3gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:traffic-cone-off" {...props}></Icon>
