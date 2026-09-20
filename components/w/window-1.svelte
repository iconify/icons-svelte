<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x4zmh5bfn.css';
import '../../css/k/krydz_bms.css';
import '../../css/m/msqmn_bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x4zmh5bfn"/><path class="krydz_bms"/><path class="msqmn_bst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:window-1" {...props}></Icon>
