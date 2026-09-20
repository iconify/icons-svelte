<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl35fttde.css';
import '../../css/f/frr8tzpij.css';
import '../../css/m/mept65bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="yl35fttde"/><path class="frr8tzpij"/><path class="mept65bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webhook-tester" {...props}></Icon>
