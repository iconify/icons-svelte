<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hws676qlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hws676qlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shield-check-line" {...props}></Icon>
