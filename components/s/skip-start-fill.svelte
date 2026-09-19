<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2qq1fjvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c2qq1fjvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-start-fill" {...props}></Icon>
