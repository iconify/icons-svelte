<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-dzk2ygk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-dzk2ygk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:upload-x" {...props}></Icon>
