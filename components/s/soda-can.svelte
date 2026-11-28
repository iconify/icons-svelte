<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd9sr7hhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd9sr7hhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:soda-can" {...props}></Icon>
