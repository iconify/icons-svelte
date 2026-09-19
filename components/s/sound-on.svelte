<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d51v3ibdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d51v3ibdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sound-on" {...props}></Icon>
