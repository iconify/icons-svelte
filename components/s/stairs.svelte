<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmv0z7b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wmv0z7b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stairs" {...props}></Icon>
