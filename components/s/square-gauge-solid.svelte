<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7muh5ncn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7muh5ncn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-gauge-solid" {...props}></Icon>
