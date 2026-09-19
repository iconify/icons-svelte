<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev-b95nln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":720,"height":780};
const content = `<path class="ev-b95nln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:thumbs" {...props}></Icon>
