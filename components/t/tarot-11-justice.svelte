<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zia8pjbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zia8pjbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-11-justice" {...props}></Icon>
