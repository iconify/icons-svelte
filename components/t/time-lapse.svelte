<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezfumgw-x.css';
import '../../css/r/rcb2foilk.css';
import '../../css/w/w0hg9ublu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ezfumgw-x"><path class="rcb2foilk"/><path class="w0hg9ublu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:time-lapse" {...props}></Icon>
