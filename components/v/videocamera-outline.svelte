<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y06ns3bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y06ns3bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:videocamera-outline" {...props}></Icon>
