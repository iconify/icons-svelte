<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pyk5dibjj.css';
import '../../css/c/cwbz9hv9b.css';
import '../../css/s/s9-lr8ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pyk5dibjj"/><path class="cwbz9hv9b"/><path class="s9-lr8ber"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:shipment-check-flat" {...props}></Icon>
