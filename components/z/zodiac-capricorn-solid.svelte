<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k51l8bchk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k51l8bchk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-capricorn-solid" {...props}></Icon>
