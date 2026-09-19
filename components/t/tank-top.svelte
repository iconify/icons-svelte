<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qad478dff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qad478dff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tank-top" {...props}></Icon>
