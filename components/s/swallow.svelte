<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc-0ae3tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qc-0ae3tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swallow" {...props}></Icon>
