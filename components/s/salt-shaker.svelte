<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhm1_nbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhm1_nbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:salt-shaker" {...props}></Icon>
