<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7hstbmu.css';
import '../../css/o/otit0l4ks.css';
import '../../css/q/qoxu7fbss.css';
import '../../css/t/tdhzq11dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><circle class="otit0l4ks"/><path class="qoxu7fbss"/><path class="tdhzq11dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:slightly-smiling-face" {...props}></Icon>
