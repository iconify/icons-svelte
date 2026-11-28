<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogg2qpwxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogg2qpwxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:truck-solid" {...props}></Icon>
