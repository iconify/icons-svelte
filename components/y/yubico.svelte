<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw6ez3bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw6ez3bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:yubico" {...props}></Icon>
