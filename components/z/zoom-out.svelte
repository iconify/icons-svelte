<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8behvorn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8behvorn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:zoom-out" {...props}></Icon>
