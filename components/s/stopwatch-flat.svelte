<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u8gg9jb5o.css';
import '../../css/z/z4033cgku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u8gg9jb5o"/><path clip-rule="evenodd" class="z4033cgku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:stopwatch-flat" {...props}></Icon>
