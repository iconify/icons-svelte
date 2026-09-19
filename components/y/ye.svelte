<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wq9270lis.css';
import '../../css/s/s2k_flldr.css';
import '../../css/y/ynt2pcbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":200};
const content = `<g class="ft5dv1b6b"><path class="wq9270lis"/><path class="s2k_flldr"/><path class="ynt2pcbub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:ye" {...props}></Icon>
