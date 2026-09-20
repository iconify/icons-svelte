<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueu0rgbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ueu0rgbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:widget3-filled" {...props}></Icon>
