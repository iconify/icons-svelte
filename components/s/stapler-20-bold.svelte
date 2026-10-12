<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_36uib7w.css';
import '../../css/t/tli9a8yok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x_36uib7w"/><path class="tli9a8yok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stapler-20-bold" {...props}></Icon>
