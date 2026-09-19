<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/a/advyo0b0z.css';
import '../../css/n/nisd5zbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="advyo0b0z"/><path class="nisd5zbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:won" {...props}></Icon>
