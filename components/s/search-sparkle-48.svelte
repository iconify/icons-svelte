<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkje3ybpz.css';
import '../../css/u/udqbpfbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gkje3ybpz"/><path class="udqbpfbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:search-sparkle-48" {...props}></Icon>
