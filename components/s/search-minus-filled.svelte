<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8yggl8mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8yggl8mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-minus-filled" {...props}></Icon>
