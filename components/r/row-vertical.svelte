<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi7nx8bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi7nx8bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:row-vertical" {...props}></Icon>
