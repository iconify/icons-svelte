<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jh2j5sozv.css';
import '../../css/k/k38s6xbay.css';
import '../../css/u/uxt7hetvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="jh2j5sozv"/><path class="k38s6xbay"/><path class="uxt7hetvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:save-one" {...props}></Icon>
