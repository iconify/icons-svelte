<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbt5gzewv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbt5gzewv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:wifi-tag-solid" {...props}></Icon>
