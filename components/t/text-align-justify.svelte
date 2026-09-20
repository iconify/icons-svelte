<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z58bjmbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z58bjmbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-align-justify" {...props}></Icon>
