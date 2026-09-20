<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip4d7ib6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip4d7ib6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:seven-waves-solid" {...props}></Icon>
