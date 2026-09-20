<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr8g-9bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr8g-9bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:send-hor-light" {...props}></Icon>
