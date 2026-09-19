<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/or_1s5gyv.css';
import '../../css/q/ql_kycc5o.css';
import '../../css/s/so4nxo65x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="or_1s5gyv"/><path class="ql_kycc5o"/><path class="so4nxo65x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shopping-card-remove-bold" {...props}></Icon>
