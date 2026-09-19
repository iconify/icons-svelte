<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puvkz5bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="puvkz5bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-pupil" {...props}></Icon>
