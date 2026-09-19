<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn3fw0byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn3fw0byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:share-ios" {...props}></Icon>
