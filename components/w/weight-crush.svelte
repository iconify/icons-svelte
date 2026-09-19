<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8ef46fbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n8ef46fbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:weight-crush" {...props}></Icon>
