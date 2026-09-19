<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh-ohcc2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh-ohcc2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:safe" {...props}></Icon>
