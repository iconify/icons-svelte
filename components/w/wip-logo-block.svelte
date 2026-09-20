<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0gv3ezgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z0gv3ezgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wip-logo-block" {...props}></Icon>
