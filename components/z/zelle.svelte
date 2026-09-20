<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1nko06zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1nko06zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zelle" {...props}></Icon>
