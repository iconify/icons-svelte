<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2-q61fsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2-q61fsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trophy-round" {...props}></Icon>
