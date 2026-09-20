<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3epgsb1m.css';
import '../../css/h/hu6j50bjd.css';
import '../../css/f/f_ebgjbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x3epgsb1m"/><path class="hu6j50bjd"/><circle class="f_ebgjbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:window-ltr" {...props}></Icon>
