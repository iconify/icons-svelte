<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zd7wexbuq.css';
import '../../css/l/lac7xcb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zd7wexbuq"/><path clip-rule="evenodd" class="lac7xcb2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:type-area-flat" {...props}></Icon>
