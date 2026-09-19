<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzvh-ba9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qzvh-ba9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:watering-can" {...props}></Icon>
