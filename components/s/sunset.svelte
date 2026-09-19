<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh-zu0p9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fh-zu0p9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sunset" {...props}></Icon>
