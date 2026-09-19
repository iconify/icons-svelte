<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o963ambkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o963ambkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sai" {...props}></Icon>
