<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vopw6rdda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vopw6rdda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:star" {...props}></Icon>
