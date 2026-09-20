<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgxhaab5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mgxhaab5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:train-kids" {...props}></Icon>
