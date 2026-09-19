<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_shbeese.css';
import '../../css/y/yn8tzubog.css';
import '../../css/g/g7i4sdbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q_shbeese"/><path class="yn8tzubog"/><path class="g7i4sdbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:shower" {...props}></Icon>
