<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax8ml37id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax8ml37id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:satellite-dish-fill-round" {...props}></Icon>
