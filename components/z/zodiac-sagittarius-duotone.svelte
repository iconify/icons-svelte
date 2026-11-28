<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czuj-ibgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czuj-ibgu primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-sagittarius-duotone" {...props}></Icon>
