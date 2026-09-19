<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjwe_m-4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjwe_m-4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sinagot" {...props}></Icon>
