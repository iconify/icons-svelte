<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ocos3pbek.css';
import '../../css/c/ch7mim7_x.css';
import '../../css/g/gh16dbbue.css';
import '../../css/l/lxhba64ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ocos3pbek"/><path class="ch7mim7_x"/><path class="gh16dbbue"/><path class="lxhba64ej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-avatar" {...props}></Icon>
