<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm098ccxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zm098ccxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waterfall-48-bold" {...props}></Icon>
