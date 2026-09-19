<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1mft8bat.css';
import '../../css/f/fr5171a8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l1mft8bat"/><path class="fr5171a8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:webpack-wordmark" {...props}></Icon>
