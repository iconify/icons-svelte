<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2_mexoqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k2_mexoqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:sign-out" {...props}></Icon>
