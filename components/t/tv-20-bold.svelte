<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn698acuz.css';
import '../../css/q/qyfrutbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mn698acuz"/><path class="qyfrutbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tv-20-bold" {...props}></Icon>
