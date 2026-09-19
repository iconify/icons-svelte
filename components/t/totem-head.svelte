<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2rq31bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w2rq31bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:totem-head" {...props}></Icon>
