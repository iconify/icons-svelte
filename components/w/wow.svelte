<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/abe4_nbce.css';
import '../../css/m/md_wqtycd.css';
import '../../css/y/yfs0kqb-c.css';
import '../../css/w/w6-q7vl-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="abe4_nbce"/><circle class="md_wqtycd"/><circle class="yfs0kqb-c"/><path class="w6-q7vl-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:wow" {...props}></Icon>
