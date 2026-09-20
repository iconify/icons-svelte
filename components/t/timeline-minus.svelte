<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sac4nqrrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sac4nqrrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-minus" {...props}></Icon>
