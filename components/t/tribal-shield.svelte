<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr9yu5bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wr9yu5bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tribal-shield" {...props}></Icon>
