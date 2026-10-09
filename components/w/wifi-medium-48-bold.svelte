<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmpmiyb4b.css';
import '../../css/v/v81ej1b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lmpmiyb4b"/><path class="v81ej1b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-medium-48-bold" {...props}></Icon>
