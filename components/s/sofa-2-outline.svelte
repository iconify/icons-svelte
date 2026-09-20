<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p33odw_cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p33odw_cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sofa-2-outline" {...props}></Icon>
