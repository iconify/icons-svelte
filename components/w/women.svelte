<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsj264bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":770,"height":1024};
const content = `<path class="hsj264bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:women" {...props}></Icon>
