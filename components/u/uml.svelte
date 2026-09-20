<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmqdv8bhv.css';
import '../../css/p/pqncy4b2j.css';
import '../../css/z/z7h6iq1vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="kmqdv8bhv"/><path class="pqncy4b2j"/><path class="z7h6iq1vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:uml" {...props}></Icon>
