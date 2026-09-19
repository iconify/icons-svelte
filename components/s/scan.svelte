<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlw6o2bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlw6o2bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:scan" {...props}></Icon>
