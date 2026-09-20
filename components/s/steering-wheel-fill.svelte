<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi95u7abw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi95u7abw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:steering-wheel-fill" {...props}></Icon>
