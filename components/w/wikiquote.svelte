<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dotp4jdox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dotp4jdox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wikiquote" {...props}></Icon>
