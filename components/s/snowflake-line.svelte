<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4bzy3bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4bzy3bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:snowflake-line" {...props}></Icon>
