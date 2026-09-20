<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_v1k8bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_v1k8bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:shield-plus-line" {...props}></Icon>
