<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1dqn_bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-0.5};
const content = `<path class="p1dqn_bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:write-f" {...props}></Icon>
