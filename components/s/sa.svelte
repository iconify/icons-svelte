<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v3cobbcjd.css';
import '../../css/t/t14-8nbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="v3cobbcjd"/><path class="t14-8nbao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:sa" {...props}></Icon>
