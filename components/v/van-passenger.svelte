<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amo08gfvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amo08gfvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:van-passenger" {...props}></Icon>
