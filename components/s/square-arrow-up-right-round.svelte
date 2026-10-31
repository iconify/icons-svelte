<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u85-a-bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u85-a-bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-arrow-up-right-round" {...props}></Icon>
