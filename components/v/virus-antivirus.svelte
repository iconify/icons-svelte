<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqax-6b-d.css';
import '../../css/p/pl_8ukb7k.css';
import '../../css/o/oh466gozg.css';
import '../../css/n/n8ly77pzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="pl_8ukb7k"/><path class="oh466gozg"/><path class="n8ly77pzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:virus-antivirus" {...props}></Icon>
