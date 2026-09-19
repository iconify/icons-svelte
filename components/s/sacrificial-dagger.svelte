<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll6m4rbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ll6m4rbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sacrificial-dagger" {...props}></Icon>
