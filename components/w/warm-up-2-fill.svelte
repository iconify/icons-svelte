<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tit07-pqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tit07-pqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:warm-up-2-fill" {...props}></Icon>
