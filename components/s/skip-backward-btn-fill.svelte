<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzv6z5blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qzv6z5blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-backward-btn-fill" {...props}></Icon>
