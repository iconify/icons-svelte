<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bun5sbcsa.css';
import '../../css/e/erw03p5yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bun5sbcsa"/><path class="erw03p5yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signpost-48-bold" {...props}></Icon>
