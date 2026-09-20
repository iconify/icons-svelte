<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4hl1acpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4hl1acpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slice-fill" {...props}></Icon>
