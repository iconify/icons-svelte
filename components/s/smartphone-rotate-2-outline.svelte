<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3-qgwb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q3-qgwb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-rotate-2-outline" {...props}></Icon>
