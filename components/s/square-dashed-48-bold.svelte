<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl0qemc8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fl0qemc8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-dashed-48-bold" {...props}></Icon>
