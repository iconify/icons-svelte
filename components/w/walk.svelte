<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjdbqjbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjdbqjbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:walk" {...props}></Icon>
