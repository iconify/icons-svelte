<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ush3tacrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ush3tacrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:send4-filled" {...props}></Icon>
