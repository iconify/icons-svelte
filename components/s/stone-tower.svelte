<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrs66hyvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qrs66hyvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stone-tower" {...props}></Icon>
