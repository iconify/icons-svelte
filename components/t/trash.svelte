<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfm5imxge.css';
import '../../css/u/u5ykzlbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rfm5imxge"/><path class="u5ykzlbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trash" {...props}></Icon>
