<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi-w9dbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi-w9dbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sunrise" {...props}></Icon>
