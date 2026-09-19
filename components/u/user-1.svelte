<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elw5i-lpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elw5i-lpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:user-1" {...props}></Icon>
