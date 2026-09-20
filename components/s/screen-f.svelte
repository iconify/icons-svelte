<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwsgpxbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="dwsgpxbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:screen-f" {...props}></Icon>
