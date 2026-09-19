<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2mr-w8gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":833,"height":1024};
const content = `<path class="v2mr-w8gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:snowman" {...props}></Icon>
