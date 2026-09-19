<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9knb0b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9knb0b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:text" {...props}></Icon>
