<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuy6n6bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuy6n6bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:upload" {...props}></Icon>
