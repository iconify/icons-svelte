<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh-o475df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh-o475df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:snapdragon" {...props}></Icon>
