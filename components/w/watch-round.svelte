<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld_j4fb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld_j4fb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:watch-round" {...props}></Icon>
