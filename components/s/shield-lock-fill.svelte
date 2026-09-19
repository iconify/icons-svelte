<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp2m2eqzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qp2m2eqzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shield-lock-fill" {...props}></Icon>
