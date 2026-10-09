<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhf6nqbcm.css';
import '../../css/k/khmlq3g6t.css';
import '../../css/b/b63ugobgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lhf6nqbcm"/><path class="khmlq3g6t"/><path class="b63ugobgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shuffle-48" {...props}></Icon>
