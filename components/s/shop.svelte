<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szat01bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szat01bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:shop" {...props}></Icon>
