<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj8l4qwvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj8l4qwvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-remove" {...props}></Icon>
