<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkn6c9j5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkn6c9j5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toy-car" {...props}></Icon>
