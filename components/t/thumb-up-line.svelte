<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-qpp8bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-qpp8bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thumb-up-line" {...props}></Icon>
