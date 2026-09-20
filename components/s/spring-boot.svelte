<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp_3f4baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp_3f4baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spring-boot" {...props}></Icon>
