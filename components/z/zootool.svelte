<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt3-jpbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":312,"height":488};
const content = `<path class="bt3-jpbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:zootool" {...props}></Icon>
