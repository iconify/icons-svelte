<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw___22ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":476,"height":512};
const content = `<path class="qw___22ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:zimpl" {...props}></Icon>
