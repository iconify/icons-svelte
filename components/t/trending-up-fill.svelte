<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmq-2ccok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmq-2ccok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trending-up-fill" {...props}></Icon>
