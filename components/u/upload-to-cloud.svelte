<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg8v1f0hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bg8v1f0hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:upload-to-cloud" {...props}></Icon>
