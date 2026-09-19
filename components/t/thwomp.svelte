<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu39jfbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gu39jfbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thwomp" {...props}></Icon>
