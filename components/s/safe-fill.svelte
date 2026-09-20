<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prqia3bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prqia3bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:safe-fill" {...props}></Icon>
