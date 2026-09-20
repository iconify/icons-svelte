<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxsp-3jny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxsp-3jny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:scroll-vertical" {...props}></Icon>
