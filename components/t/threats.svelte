<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn560_avf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn560_avf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:threats" {...props}></Icon>
