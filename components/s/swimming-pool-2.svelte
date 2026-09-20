<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mab8s_msf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mab8s_msf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:swimming-pool-2" {...props}></Icon>
