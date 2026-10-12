<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zewt6pbzu.css';
import '../../css/m/m6mj_obaa.css';
import '../../css/p/pnmyt_1ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zewt6pbzu"/><path class="m6mj_obaa"/><path class="pnmyt_1ej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:thermometer-snowflake-duotone" {...props}></Icon>
