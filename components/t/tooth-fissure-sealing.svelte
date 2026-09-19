<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8ywor6vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8ywor6vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-fissure-sealing" {...props}></Icon>
