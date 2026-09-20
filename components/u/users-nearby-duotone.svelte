<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cv40bhlsq.css';
import '../../css/c/ch1ctkp8j.css';
import '../../css/l/lb3khzbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cv40bhlsq"/><path clip-rule="evenodd" class="ch1ctkp8j"/><path class="lb3khzbez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:users-nearby-duotone" {...props}></Icon>
