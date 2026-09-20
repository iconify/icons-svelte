<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_ku7fb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k_ku7fb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sun-outline" {...props}></Icon>
