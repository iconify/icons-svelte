<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqd8fcboz.css';
import '../../css/d/dzr6cgbld.css';
import '../../css/p/pg7ja1biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><path class="dzr6cgbld"/><path class="pg7ja1biu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gala:video" {...props}></Icon>
