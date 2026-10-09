<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db7nnwbjm.css';
import '../../css/j/jdfj84bsl.css';
import '../../css/k/ka2s7tbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="db7nnwbjm"/><path class="jdfj84bsl"/><path class="ka2s7tbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sprout-20" {...props}></Icon>
