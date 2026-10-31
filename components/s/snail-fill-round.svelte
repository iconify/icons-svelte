<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we8g2n_pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we8g2n_pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:snail-fill-round" {...props}></Icon>
