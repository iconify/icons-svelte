<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/uhlhzujjg.css';
import '../../css/p/pkwdlrb9z.css';
import '../../css/g/gyi273b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="uhlhzujjg"/><path class="pkwdlrb9z"/><path class="gyi273b3s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:save-light" {...props}></Icon>
