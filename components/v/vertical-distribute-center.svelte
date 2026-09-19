<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn8j55bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn8j55bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-distribute-center" {...props}></Icon>
