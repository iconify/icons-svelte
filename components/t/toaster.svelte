<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljj7i8b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljj7i8b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:toaster" {...props}></Icon>
