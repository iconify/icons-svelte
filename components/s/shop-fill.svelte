<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-_jgm2kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-_jgm2kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shop-fill" {...props}></Icon>
