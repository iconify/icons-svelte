<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kavo--bbr.css';
import '../../css/l/ll5uu22sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kavo--bbr"/><path class="ll5uu22sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-48-bold" {...props}></Icon>
