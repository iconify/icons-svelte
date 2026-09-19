<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz8waubmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gz8waubmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:surprised" {...props}></Icon>
