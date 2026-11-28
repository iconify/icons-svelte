<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgs59abro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgs59abro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle-dashed-solid" {...props}></Icon>
