<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhgy8ebgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhgy8ebgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:standing-potion" {...props}></Icon>
