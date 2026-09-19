<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di_vi8bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="di_vi8bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tec-9" {...props}></Icon>
