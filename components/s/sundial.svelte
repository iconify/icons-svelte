<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofvr41bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ofvr41bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sundial" {...props}></Icon>
