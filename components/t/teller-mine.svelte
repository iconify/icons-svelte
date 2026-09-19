<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khjiklbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="khjiklbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:teller-mine" {...props}></Icon>
