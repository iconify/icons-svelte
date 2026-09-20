<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtcavo2ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtcavo2ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:textalign-justifycenter-filled" {...props}></Icon>
