<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypby706kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypby706kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tram-solid" {...props}></Icon>
