<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d93kgmbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d93kgmbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-forward-btn-fill" {...props}></Icon>
