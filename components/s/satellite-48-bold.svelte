<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia6zlxdrk.css';
import '../../css/w/wp13yub7p.css';
import '../../css/c/cl2lae65c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ia6zlxdrk"/><path class="wp13yub7p"/><path class="cl2lae65c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:satellite-48-bold" {...props}></Icon>
