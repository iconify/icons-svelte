<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7duwgmiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7duwgmiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shirt-fill" {...props}></Icon>
