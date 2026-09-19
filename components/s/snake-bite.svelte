<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_k843sjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_k843sjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snake-bite" {...props}></Icon>
