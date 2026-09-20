<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo_h-m8ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo_h-m8ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-security-fill" {...props}></Icon>
