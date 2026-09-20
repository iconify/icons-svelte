<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egr5g34zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egr5g34zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:save-2-fill" {...props}></Icon>
