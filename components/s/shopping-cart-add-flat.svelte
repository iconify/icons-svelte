<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pzivvmyfh.css';
import '../../css/z/zvuztsblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pzivvmyfh"/><path class="zvuztsblu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:shopping-cart-add-flat" {...props}></Icon>
