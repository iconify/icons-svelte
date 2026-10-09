<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwfb0b_qf.css';
import '../../css/q/qxaxj2trm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qwfb0b_qf"/><path class="qxaxj2trm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:run-of-river-20" {...props}></Icon>
