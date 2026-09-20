<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjn7-gbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjn7-gbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:taipy" {...props}></Icon>
