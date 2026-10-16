<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksschrb-d.css';
import '../../css/q/qy95ayb8d.css';
import '../../css/g/g3wis4bce.css';
import '../../css/t/tsy-snfbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ksschrb-d"/><path class="qy95ayb8d"/><path class="g3wis4bce"/><path class="tsy-snfbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wheelbarrow-20-bold" {...props}></Icon>
