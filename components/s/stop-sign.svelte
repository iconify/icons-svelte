<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_mgn5bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_mgn5bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stop-sign" {...props}></Icon>
