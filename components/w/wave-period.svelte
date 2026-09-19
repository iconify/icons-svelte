<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-ixdzbom.css';
import '../../css/f/ffofn9bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c-ixdzbom"/><path class="ffofn9bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wave-period" {...props}></Icon>
