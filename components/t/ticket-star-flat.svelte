<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s4j5v5x8u.css';
import '../../css/r/r9uapkbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s4j5v5x8u"/><path clip-rule="evenodd" class="r9uapkbwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:ticket-star-flat" {...props}></Icon>
