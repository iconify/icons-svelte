<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or0cs6mcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or0cs6mcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scan-search" {...props}></Icon>
