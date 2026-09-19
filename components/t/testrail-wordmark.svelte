<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viy1tfbqb.css';
import '../../css/g/gge4koq5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="viy1tfbqb"/><path class="gge4koq5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:testrail-wordmark" {...props}></Icon>
