<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opcf11c4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opcf11c4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:wrench" {...props}></Icon>
