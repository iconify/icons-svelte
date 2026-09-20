<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec7eydbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec7eydbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-right-line" {...props}></Icon>
