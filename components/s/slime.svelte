<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj9z3ob_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qj9z3ob_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:slime" {...props}></Icon>
