<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khy_1bp6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="khy_1bp6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:scanning" {...props}></Icon>
