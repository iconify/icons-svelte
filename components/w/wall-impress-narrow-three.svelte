<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-3b9lb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-3b9lb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-impress-narrow-three" {...props}></Icon>
