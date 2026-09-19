<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-5v66b_l.css';
import '../../css/h/hj7x4zb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-5v66b_l"/><path class="hj7x4zb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:watch" {...props}></Icon>
