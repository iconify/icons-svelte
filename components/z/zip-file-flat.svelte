<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ckc_8ib1x.css';
import '../../css/b/bctvapb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ckc_8ib1x"/><path clip-rule="evenodd" class="bctvapb7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:zip-file-flat" {...props}></Icon>
