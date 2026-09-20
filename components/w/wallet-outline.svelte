<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uggz1wboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uggz1wboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wallet-outline" {...props}></Icon>
