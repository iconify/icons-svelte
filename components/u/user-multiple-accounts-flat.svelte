<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lo1dnac6c.css';
import '../../css/z/zp6ey7xyk.css';
import '../../css/s/sv6qal5dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lo1dnac6c"/><path class="zp6ey7xyk"/><path class="sv6qal5dy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:user-multiple-accounts-flat" {...props}></Icon>
