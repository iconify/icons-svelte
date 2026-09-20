<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u665ban.css';
import '../../css/i/ita_uwbar.css';
import '../../css/u/urrkr9byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="ita_uwbar"/><path class="urrkr9byt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:webcam-video" {...props}></Icon>
