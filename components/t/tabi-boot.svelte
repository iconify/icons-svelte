<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3_otkb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3_otkb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tabi-boot" {...props}></Icon>
