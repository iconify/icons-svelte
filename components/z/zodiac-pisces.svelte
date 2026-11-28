<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i8g04wnih.css';
import '../../css/p/p9jlw9bmd.css';
import '../../css/n/npnurpite.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i8g04wnih"/><path class="p9jlw9bmd"/><path class="npnurpite"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-pisces" {...props}></Icon>
