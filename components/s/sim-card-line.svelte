<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yghw7-75z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yghw7-75z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:sim-card-line" {...props}></Icon>
