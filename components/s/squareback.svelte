<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp388_vra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zp388_vra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squareback" {...props}></Icon>
