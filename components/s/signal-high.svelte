<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b68na8seu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b68na8seu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:signal-high" {...props}></Icon>
