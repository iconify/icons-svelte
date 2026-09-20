<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/g/gufd03s5p.css';
import '../../css/v/velahuttd.css';
import '../../css/y/y2ls4efbx.css';
import '../../css/y/y-frmvbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><rect class="gufd03s5p"/><rect class="velahuttd"/><rect class="y2ls4efbx"/><path class="y-frmvbsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:widget-add-light" {...props}></Icon>
