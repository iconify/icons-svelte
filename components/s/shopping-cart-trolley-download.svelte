<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/d64aytbpv.css';
import '../../css/r/rqxh9mzju.css';
import '../../css/u/ubjfz4bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="d64aytbpv"/><path class="rqxh9mzju"/><path class="ubjfz4bbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:shopping-cart-trolley-download" {...props}></Icon>
