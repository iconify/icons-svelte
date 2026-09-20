<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/dhgwwr1yb.css';
import '../../css/l/lazoeb1xt.css';
import '../../css/j/j987dacbq.css';
import '../../css/k/k10idobrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="dhgwwr1yb"/><path class="lazoeb1xt"/><path class="j987dacbq"/><path class="k10idobrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:yuan" {...props}></Icon>
