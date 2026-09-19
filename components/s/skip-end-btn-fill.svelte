<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwshshvdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zwshshvdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-end-btn-fill" {...props}></Icon>
