<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2hyr4bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b2hyr4bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tapir" {...props}></Icon>
