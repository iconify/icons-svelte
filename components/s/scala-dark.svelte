<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/v/vlulgsbdg.css';
import '../../css/m/mvb1mnblt.css';
import '../../css/f/fz-dd5bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path clip-rule="evenodd" class="vlulgsbdg"/><path clip-rule="evenodd" class="mvb1mnblt"/><path clip-rule="evenodd" class="fz-dd5bhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:scala-dark" {...props}></Icon>
