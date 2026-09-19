<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4f69cbip.css';
import '../../css/p/paxrevb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4f69cbip"/><path class="paxrevb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:save-down-2" {...props}></Icon>
