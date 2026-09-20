<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzjrsmbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzjrsmbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shut-down-fill" {...props}></Icon>
