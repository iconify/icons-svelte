<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2l3_-b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h2l3_-b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:star-badge-solid" {...props}></Icon>
