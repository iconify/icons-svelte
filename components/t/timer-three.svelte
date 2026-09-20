<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awwgdy2er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awwgdy2er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-three" {...props}></Icon>
