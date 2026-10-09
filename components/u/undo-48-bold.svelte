<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3w_jjzoh.css';
import '../../css/f/fu6xpoo5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l3w_jjzoh"/><path class="fu6xpoo5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:undo-48-bold" {...props}></Icon>
