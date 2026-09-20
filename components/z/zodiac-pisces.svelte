<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/torobyboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="torobyboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:zodiac-pisces" {...props}></Icon>
