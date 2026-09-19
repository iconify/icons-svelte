<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa31awb9o.css';
import '../../css/j/jdjzcnbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa31awb9o"/><path class="jdjzcnbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:youtube-music" {...props}></Icon>
