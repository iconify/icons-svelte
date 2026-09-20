<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmit9yp1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmit9yp1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-rotate-orientation-outline" {...props}></Icon>
