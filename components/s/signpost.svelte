<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chst1zbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chst1zbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:signpost" {...props}></Icon>
