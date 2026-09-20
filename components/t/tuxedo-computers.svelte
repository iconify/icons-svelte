<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa6r-zkqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa6r-zkqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tuxedo-computers" {...props}></Icon>
