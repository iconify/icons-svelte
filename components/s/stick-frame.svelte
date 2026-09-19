<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksgi1ebim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksgi1ebim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stick-frame" {...props}></Icon>
