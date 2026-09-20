<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxj45rbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxj45rbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:scissors" {...props}></Icon>
