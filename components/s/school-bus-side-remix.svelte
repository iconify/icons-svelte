<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h71up4bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h71up4bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:school-bus-side-remix" {...props}></Icon>
