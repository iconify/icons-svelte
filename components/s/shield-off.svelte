<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3xk5bt5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3xk5bt5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:shield-off" {...props}></Icon>
