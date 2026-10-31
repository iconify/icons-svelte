<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e21ipqbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e21ipqbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:swatches-fill-round" {...props}></Icon>
