<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srtboqkek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary srtboqkek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-libra-duotone" {...props}></Icon>
