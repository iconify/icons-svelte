<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k_7v9l6pn.css';
import '../../css/g/gxdfmzjck.css';
import '../../css/h/hw0kxtbhp.css';
import '../../css/p/pifh3f0yj.css';
import '../../css/o/oquvwwkbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="k_7v9l6pn"/><path class="gxdfmzjck"/><circle class="hw0kxtbhp"/><circle class="pifh3f0yj"/><path class="oquvwwkbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:tabletennis" {...props}></Icon>
