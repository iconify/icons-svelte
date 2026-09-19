<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/iim7lrbsa.css';
import '../../css/w/wcn22lccd.css';
import '../../css/y/yl2qgibmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="iim7lrbsa"/><path class="wcn22lccd"/><path class="yl2qgibmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:store-03" {...props}></Icon>
