<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arilcpb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="arilcpb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:velociraptor" {...props}></Icon>
