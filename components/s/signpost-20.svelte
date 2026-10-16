<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uma6ucy9m.css';
import '../../css/f/f-a0_gbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uma6ucy9m"/><path class="f-a0_gbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signpost-20" {...props}></Icon>
