<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q58kriblw.css';
import '../../css/t/tc02e-b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q58kriblw"/><path class="tc02e-b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:soccerball" {...props}></Icon>
