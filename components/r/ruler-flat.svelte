<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yr7m05v4v.css';
import '../../css/y/yrh_v73eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yr7m05v4v"/><path clip-rule="evenodd" class="yrh_v73eb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:ruler-flat" {...props}></Icon>
