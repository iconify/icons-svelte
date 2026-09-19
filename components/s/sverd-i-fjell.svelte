<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk2e_09ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uk2e_09ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sverd-i-fjell" {...props}></Icon>
