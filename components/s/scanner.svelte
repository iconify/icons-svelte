<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv3b-bb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv3b-bb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:scanner" {...props}></Icon>
