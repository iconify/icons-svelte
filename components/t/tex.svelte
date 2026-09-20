<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tow6czris.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tow6czris"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tex" {...props}></Icon>
