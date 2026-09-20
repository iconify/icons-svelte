<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm05gabfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm05gabfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tuta" {...props}></Icon>
