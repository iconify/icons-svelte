<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npziikbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npziikbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ufo-fill" {...props}></Icon>
