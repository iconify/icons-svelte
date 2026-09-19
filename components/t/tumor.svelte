<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej4ripj1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ej4ripj1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tumor" {...props}></Icon>
