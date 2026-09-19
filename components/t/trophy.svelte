<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r39_0xs4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r39_0xs4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:trophy" {...props}></Icon>
