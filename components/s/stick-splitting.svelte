<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1e6a6b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1e6a6b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stick-splitting" {...props}></Icon>
