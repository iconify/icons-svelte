<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gto01yb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gto01yb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:wine-bottle-glass" {...props}></Icon>
