<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alvduwk6p.css';
import '../../css/g/g7x2tg8pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alvduwk6p"/><path class="g7x2tg8pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:soroswap" {...props}></Icon>
