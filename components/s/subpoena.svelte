<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/p4nocrihx.css';
import '../../css/v/v_rcp4-4p.css';
import '../../css/o/okx5q-b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="p4nocrihx"/><path class="v_rcp4-4p"/><path class="okx5q-b1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:subpoena" {...props}></Icon>
