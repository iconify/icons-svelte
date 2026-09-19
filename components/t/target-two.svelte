<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3dpzbtra.css';
import '../../css/o/obna4oqji.css';
import '../../css/v/v0nd3ac9a.css';
import '../../css/e/ercysii-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="obna4oqji"/><path class="v0nd3ac9a"/><path class="ercysii-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:target-two" {...props}></Icon>
