<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsdjueb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsdjueb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:triangle-down" {...props}></Icon>
