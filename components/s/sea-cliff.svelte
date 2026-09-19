<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8uc9-brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n8uc9-brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sea-cliff" {...props}></Icon>
