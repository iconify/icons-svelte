<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc1_vptuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cc1_vptuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:toilet-paper-solid" {...props}></Icon>
