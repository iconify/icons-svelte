<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd526em5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd526em5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-6-line" {...props}></Icon>
