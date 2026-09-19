<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp0wpw-wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mp0wpw-wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitequestionmark" {...props}></Icon>
