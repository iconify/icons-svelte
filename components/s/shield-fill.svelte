<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwuu_8brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dwuu_8brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shield-fill" {...props}></Icon>
