<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt0e9ox5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1408};
const content = `<path class="gt0e9ox5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:square-o" {...props}></Icon>
