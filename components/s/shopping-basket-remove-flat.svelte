<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vy6frvpsh.css';
import '../../css/l/ltxit21ma.css';
import '../../css/z/z9j_ljb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vy6frvpsh"/><path class="ltxit21ma"/><path class="z9j_ljb5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:shopping-basket-remove-flat" {...props}></Icon>
