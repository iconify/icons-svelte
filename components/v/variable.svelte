<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnj6icb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnj6icb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:variable" {...props}></Icon>
