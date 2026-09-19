<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9w22fbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z9w22fbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wok" {...props}></Icon>
