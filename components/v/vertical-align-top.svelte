<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glh0c68sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glh0c68sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-align-top" {...props}></Icon>
