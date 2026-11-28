<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq1ek_buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq1ek_buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-pi-solid" {...props}></Icon>
