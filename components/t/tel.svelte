<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llq8mab9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llq8mab9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tel" {...props}></Icon>
