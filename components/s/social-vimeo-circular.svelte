<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu1961ykc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu1961ykc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-vimeo-circular" {...props}></Icon>
