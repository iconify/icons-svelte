<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuogg0oyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iuogg0oyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sinking-trap" {...props}></Icon>
