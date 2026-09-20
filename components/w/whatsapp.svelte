<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io6e_qbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io6e_qbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:whatsapp" {...props}></Icon>
