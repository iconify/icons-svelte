<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut-0zoohp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut-0zoohp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-sagittarius-solid" {...props}></Icon>
