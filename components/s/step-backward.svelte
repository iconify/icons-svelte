<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie2opebeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie2opebeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:step-backward" {...props}></Icon>
