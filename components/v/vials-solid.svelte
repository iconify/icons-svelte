<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9uetabbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9uetabbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vials-solid" {...props}></Icon>
