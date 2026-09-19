<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqy36v4km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqy36v4km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:text-align-full" {...props}></Icon>
