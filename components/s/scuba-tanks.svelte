<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow77t97lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow77t97lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scuba-tanks" {...props}></Icon>
