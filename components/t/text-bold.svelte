<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6g817zjy.css';
import '../../css/k/k3nn7hxsv.css';
import '../../css/y/yto2jk_qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="o6g817zjy"><path class="k3nn7hxsv"/><path class="yto2jk_qy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:text-bold" {...props}></Icon>
