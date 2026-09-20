<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7x8lrbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7x8lrbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:shadow" {...props}></Icon>
