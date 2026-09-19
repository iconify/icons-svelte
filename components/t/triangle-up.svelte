<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzyh82htk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gzyh82htk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:triangle-up" {...props}></Icon>
