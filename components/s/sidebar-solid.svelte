<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnc4pvh2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnc4pvh2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sidebar-solid" {...props}></Icon>
