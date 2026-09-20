<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kepg9yfyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kepg9yfyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:thumbs-down" {...props}></Icon>
