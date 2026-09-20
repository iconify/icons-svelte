<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obib_9bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obib_9bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:terminal" {...props}></Icon>
