<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sns089f0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sns089f0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:waves" {...props}></Icon>
