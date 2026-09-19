<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8c6baceh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8c6baceh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shell" {...props}></Icon>
