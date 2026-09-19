<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q5bvs4b8s.css';
import '../../css/x/xejwnnbvm.css';
import '../../css/i/iqjbqp6jg.css';
import '../../css/d/d74nj3bga.css';
import '../../css/q/qahz-0dvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q5bvs4b8s"/><path class="xejwnnbvm"/><path class="iqjbqp6jg"/><path class="d74nj3bga"/><path class="qahz-0dvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:school-bus" {...props}></Icon>
