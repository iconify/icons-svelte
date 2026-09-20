<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t818vw59i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t818vw59i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:window-open" {...props}></Icon>
