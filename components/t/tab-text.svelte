<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx3ur7rfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx3ur7rfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:tab-text" {...props}></Icon>
