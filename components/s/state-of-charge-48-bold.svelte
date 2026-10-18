<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj-lzbb4z.css';
import '../../css/s/symaru7nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nj-lzbb4z"/><path class="symaru7nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:state-of-charge-48-bold" {...props}></Icon>
