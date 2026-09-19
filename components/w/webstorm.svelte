<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp_m6ccqt.css';
import '../../css/w/w9zfbqsgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp_m6ccqt"/><path class="w9zfbqsgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:webstorm" {...props}></Icon>
