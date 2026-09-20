<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3re9eibs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3re9eibs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:singapore-airlines" {...props}></Icon>
