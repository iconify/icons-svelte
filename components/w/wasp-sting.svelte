<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rukyg-b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rukyg-b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wasp-sting" {...props}></Icon>
