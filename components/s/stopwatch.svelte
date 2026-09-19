<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/v-0rjvvza.css';
import '../../css/x/xeuun3anw.css';
import '../../css/x/xefukylla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="v-0rjvvza"/><path class="xeuun3anw"/><path class="xefukylla"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:stopwatch" {...props}></Icon>
