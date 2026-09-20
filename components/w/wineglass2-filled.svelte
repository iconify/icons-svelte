<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekn5macxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekn5macxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wineglass2-filled" {...props}></Icon>
