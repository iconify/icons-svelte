<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfwk4ub9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfwk4ub9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-sidebar-fill-round" {...props}></Icon>
