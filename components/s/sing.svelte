<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzx3rkyyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tzx3rkyyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sing" {...props}></Icon>
