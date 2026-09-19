<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n377csbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n377csbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tribal-pendant" {...props}></Icon>
