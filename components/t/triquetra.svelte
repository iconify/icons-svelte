<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-esylbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-esylbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:triquetra" {...props}></Icon>
