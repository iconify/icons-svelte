<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt6t-acux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt6t-acux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-clock-outline" {...props}></Icon>
