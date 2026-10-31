<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/nv44gjb1e.css';
import '../../css/b/btdmjfbdm.css';
import '../../css/h/hoeyknbxx.css';
import '../../css/i/i_gylybvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="nv44gjb1e wm-shadow"/><path class="btdmjfbdm wm-shadow"/><path class="hoeyknbxx"/><path class="i_gylybvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:tombstone" {...props}></Icon>
