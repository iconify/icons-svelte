<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir6r4qmdm.css';
import '../../css/l/lfvfo_aeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ir6r4qmdm"/><path class="lfvfo_aeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wardrobe-48-bold" {...props}></Icon>
