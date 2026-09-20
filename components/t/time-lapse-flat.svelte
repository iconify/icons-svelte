<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rhfeptotx.css';
import '../../css/o/obwtx-c8u.css';
import '../../css/v/vef42hohb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rhfeptotx"/><path class="obwtx-c8u"/><path class="vef42hohb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:time-lapse-flat" {...props}></Icon>
