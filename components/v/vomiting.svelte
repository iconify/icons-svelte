<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7h3y_73d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7h3y_73d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vomiting" {...props}></Icon>
