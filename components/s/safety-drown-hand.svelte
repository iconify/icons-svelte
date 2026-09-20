<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knumxct5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knumxct5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:safety-drown-hand" {...props}></Icon>
