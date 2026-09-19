<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncmxldb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ncmxldb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:turnstile" {...props}></Icon>
