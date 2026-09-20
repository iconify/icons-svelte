<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/x_9dq4bdy.css';
import '../../css/o/oxc64zbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x_9dq4bdy"/><path clip-rule="evenodd" class="oxc64zbus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:swatch-book-sharp-fill" {...props}></Icon>
