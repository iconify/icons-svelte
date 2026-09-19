<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9z9uobwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d9z9uobwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:space-shuttle" {...props}></Icon>
