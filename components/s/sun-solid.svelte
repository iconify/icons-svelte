<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1-7subbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k1-7subbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sun-solid" {...props}></Icon>
