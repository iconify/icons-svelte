<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e53o5ubcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e53o5ubcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:toy-brick" {...props}></Icon>
