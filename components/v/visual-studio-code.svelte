<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7t7plf6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7t7plf6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:visual-studio-code" {...props}></Icon>
