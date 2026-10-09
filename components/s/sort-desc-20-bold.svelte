<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6l3rqbjj.css';
import '../../css/q/qzqnbpaip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6l3rqbjj"/><path class="qzqnbpaip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-desc-20-bold" {...props}></Icon>
