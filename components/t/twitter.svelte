<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dni5ktknm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dni5ktknm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:twitter" {...props}></Icon>
