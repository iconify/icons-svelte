<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/romdbj0mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="romdbj0mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tourbox" {...props}></Icon>
