<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dktm0rvez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dktm0rvez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zodiac-pisces" {...props}></Icon>
