<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpfoavhwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dpfoavhwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shield-reflect" {...props}></Icon>
