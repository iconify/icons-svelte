<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqd8fcboz.css';
import '../../css/w/w1s23mb7s.css';
import '../../css/m/mwa85c6im.css';
import '../../css/e/ex9ju6btd.css';
import '../../css/b/bc6kks3tc.css';
import '../../css/t/tj4aydbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><path class="w1s23mb7s"/><path class="mwa85c6im"/><path class="ex9ju6btd"/><path class="bc6kks3tc"/><path class="tj4aydbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gala:shield" {...props}></Icon>
