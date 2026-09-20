<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjc_zt5-d.css';
import '../../css/c/cr5oxtb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qjc_zt5-d"/><path class="cr5oxtb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ups" {...props}></Icon>
