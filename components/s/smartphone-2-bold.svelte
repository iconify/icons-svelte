<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clz8sab3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="clz8sab3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-2-bold" {...props}></Icon>
