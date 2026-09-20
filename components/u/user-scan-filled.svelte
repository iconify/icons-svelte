<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip6m2qbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip6m2qbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-scan-filled" {...props}></Icon>
