<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahpckbcel.css';
import '../../css/e/e-5v66b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahpckbcel"/><path class="e-5v66b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wrist-watch-round" {...props}></Icon>
