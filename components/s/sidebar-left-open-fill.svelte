<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx8fw-bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx8fw-bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-left-open-fill" {...props}></Icon>
