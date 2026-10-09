<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovky5ebwk.css';
import '../../css/e/e0581abux.css';
import '../../css/v/vkg-d9byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ovky5ebwk"/><path class="e0581abux"/><path class="vkg-d9byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shrink-20-bold" {...props}></Icon>
