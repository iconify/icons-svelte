<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7dzpxqys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x7dzpxqys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snake-totem" {...props}></Icon>
