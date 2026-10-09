<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn7333whg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qn7333whg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-none-48-bold" {...props}></Icon>
