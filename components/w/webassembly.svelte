<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snt7n62gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snt7n62gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:webassembly" {...props}></Icon>
