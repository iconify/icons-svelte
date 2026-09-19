<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/ytyivubup.css';
import '../../css/g/gieyr613j.css';
import '../../css/i/ipm6erbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ytyivubup"/><path class="gieyr613j"/><circle class="ipm6erbuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:u-turn-right" {...props}></Icon>
