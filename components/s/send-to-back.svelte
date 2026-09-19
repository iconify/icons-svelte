<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkewu7bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkewu7bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:send-to-back" {...props}></Icon>
