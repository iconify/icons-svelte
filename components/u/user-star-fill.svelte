<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cftcxm0cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cftcxm0cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-star-fill" {...props}></Icon>
