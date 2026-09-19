<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmo20pbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmo20pbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:small-lamp" {...props}></Icon>
