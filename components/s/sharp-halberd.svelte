<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otfv3cb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="otfv3cb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sharp-halberd" {...props}></Icon>
