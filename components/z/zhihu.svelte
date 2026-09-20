<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2sa-schs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2sa-schs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zhihu" {...props}></Icon>
