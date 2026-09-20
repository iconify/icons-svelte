<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc2-d7bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc2-d7bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:table-of-contents" {...props}></Icon>
