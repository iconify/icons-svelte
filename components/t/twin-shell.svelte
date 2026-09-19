<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdlbsc1hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdlbsc1hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:twin-shell" {...props}></Icon>
