<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wieq7wj0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wieq7wj0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:statom" {...props}></Icon>
