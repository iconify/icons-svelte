<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdvk43bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdvk43bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:smile-solid" {...props}></Icon>
