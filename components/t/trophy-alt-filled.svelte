<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j85fdy7uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j85fdy7uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:trophy-alt-filled" {...props}></Icon>
