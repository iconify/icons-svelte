<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve8ocsp6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ve8ocsp6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:taxi-front-fill" {...props}></Icon>
