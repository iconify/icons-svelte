<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8u8d-z0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="x8u8d-z0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:triangle" {...props}></Icon>
