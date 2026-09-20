<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa_nwxbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa_nwxbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scaleway" {...props}></Icon>
