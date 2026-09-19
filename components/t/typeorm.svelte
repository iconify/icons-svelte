<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky_82sbmu.css';
import '../../css/o/okeacwbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ky_82sbmu"/><path class="okeacwbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:typeorm" {...props}></Icon>
