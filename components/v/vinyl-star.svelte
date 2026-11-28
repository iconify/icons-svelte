<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hik7flbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hik7flbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:vinyl-star" {...props}></Icon>
