<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpwb5tbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpwb5tbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:square-root" {...props}></Icon>
