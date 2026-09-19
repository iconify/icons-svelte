<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k27mx3b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k27mx3b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiky-pit" {...props}></Icon>
