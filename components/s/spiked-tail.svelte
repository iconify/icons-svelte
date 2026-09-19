<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic-85ejwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ic-85ejwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-tail" {...props}></Icon>
