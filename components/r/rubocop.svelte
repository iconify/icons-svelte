<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebbz1ybvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":433,"height":512};
const content = `<path class="ebbz1ybvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rubocop" {...props}></Icon>
