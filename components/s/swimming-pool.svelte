<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml4dr2hga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ml4dr2hga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:swimming-pool" {...props}></Icon>
