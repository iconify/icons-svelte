<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doex5ofaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doex5ofaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:search-outline" {...props}></Icon>
