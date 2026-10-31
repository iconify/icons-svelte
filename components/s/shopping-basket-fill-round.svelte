<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td43dj0tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td43dj0tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-basket-fill-round" {...props}></Icon>
