<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lda668b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lda668b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wood-pellets-20-bold" {...props}></Icon>
