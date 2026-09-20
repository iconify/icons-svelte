<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff2r-ybjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff2r-ybjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:telegraph" {...props}></Icon>
