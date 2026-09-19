<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fxlqk9beh.css';
import '../../css/y/yo439s51q.css';
import '../../css/c/cs4v2ib4u.css';
import '../../css/u/uuoiwqtfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="fxlqk9beh"/><path class="yo439s51q"/><path class="cs4v2ib4u"/><path class="uuoiwqtfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sapling" {...props}></Icon>
