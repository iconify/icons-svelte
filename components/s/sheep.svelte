<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shs3c61cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shs3c61cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sheep" {...props}></Icon>
