<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/l/l8tiy2eeu.css';
import '../../css/n/n1j1stbmb.css';
import '../../css/j/j7jrpp0bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="l8tiy2eeu"/><path class="n1j1stbmb"/><path class="j7jrpp0bb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sms-edit" {...props}></Icon>
