<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/q/q4z7accis.css';
import '../../css/r/rqbsb5yod.css';
import '../../css/b/b7h7ulb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="q4z7accis"/><path class="rqbsb5yod"/><path class="b7h7ulb6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:target-outline" {...props}></Icon>
