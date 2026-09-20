<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaepvkbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaepvkbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:scan" {...props}></Icon>
