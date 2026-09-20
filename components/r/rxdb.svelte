<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuan0__fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuan0__fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rxdb" {...props}></Icon>
