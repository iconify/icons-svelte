<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpz5whbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpz5whbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thumbs-down-solid" {...props}></Icon>
