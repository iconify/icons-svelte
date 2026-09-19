<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff_8p9-to.css';
import '../../css/e/e8au8db-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ff_8p9-to"/><path class="e8au8db-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:triangularruler" {...props}></Icon>
