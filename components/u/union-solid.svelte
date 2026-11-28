<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpcwetbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpcwetbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:union-solid" {...props}></Icon>
