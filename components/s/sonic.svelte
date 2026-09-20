<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p49a8zbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p49a8zbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sonic" {...props}></Icon>
