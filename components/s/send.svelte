<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhd-_sbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhd-_sbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:send" {...props}></Icon>
