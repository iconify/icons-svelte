<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwghp2zfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gwghp2zfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trophies-shelf" {...props}></Icon>
