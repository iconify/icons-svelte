<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwhj3zbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwhj3zbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vimeo" {...props}></Icon>
