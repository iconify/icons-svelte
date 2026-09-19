<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sow_kcxxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sow_kcxxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:wrench" {...props}></Icon>
