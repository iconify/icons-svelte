<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6t2bcbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6t2bcbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-left-close-fill" {...props}></Icon>
