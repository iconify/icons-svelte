<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_1kf0icu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_1kf0icu primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-cancer-duotone" {...props}></Icon>
