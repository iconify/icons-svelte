<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o80_k_51n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o80_k_51n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sd-card-fill" {...props}></Icon>
