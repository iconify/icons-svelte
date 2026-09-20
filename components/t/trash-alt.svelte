<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5iq8cb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="y5iq8cb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:trash-alt" {...props}></Icon>
