<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_pniu6wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_pniu6wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stop-circle-outline" {...props}></Icon>
