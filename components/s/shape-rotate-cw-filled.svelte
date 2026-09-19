<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcl2e-hth.css';
import '../../css/d/dnt6pzbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcl2e-hth"/><path class="dnt6pzbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-rotate-cw-filled" {...props}></Icon>
