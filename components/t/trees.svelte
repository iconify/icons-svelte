<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr9_81qpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr9_81qpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:trees" {...props}></Icon>
