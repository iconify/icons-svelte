<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy6r-4lmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy6r-4lmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:suzuki" {...props}></Icon>
