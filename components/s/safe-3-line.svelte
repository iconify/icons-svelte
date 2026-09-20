<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9t_8ob2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9t_8ob2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:safe-3-line" {...props}></Icon>
