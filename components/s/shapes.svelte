<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_gdq_l-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_gdq_l-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shapes" {...props}></Icon>
