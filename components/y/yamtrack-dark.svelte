<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg5ptdx_f.css';
import '../../css/h/hclia1bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="qg5ptdx_f"/><path class="hclia1bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yamtrack-dark" {...props}></Icon>
