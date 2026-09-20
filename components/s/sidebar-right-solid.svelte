<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh1t4oi3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh1t4oi3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:sidebar-right-solid" {...props}></Icon>
