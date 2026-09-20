<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsz6ymzym.css';
import '../../css/i/infp_-iqz.css';
import '../../css/t/tkcb4abzj.css';
import '../../css/p/pd0d71b8i.css';
import '../../css/i/ido_hw-bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="jsz6ymzym"><path class="infp_-iqz"/><circle class="tkcb4abzj"/></g><circle class="pd0d71b8i"/><path class="ido_hw-bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-question-mark" {...props}></Icon>
