<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-3o8k8yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-3o8k8yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:subway" {...props}></Icon>
