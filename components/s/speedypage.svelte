<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evo-p5yty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evo-p5yty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:speedypage" {...props}></Icon>
