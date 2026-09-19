<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyxy32_gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gyxy32_gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snake" {...props}></Icon>
