<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8g6tm0he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="o8g6tm0he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:sentry" {...props}></Icon>
