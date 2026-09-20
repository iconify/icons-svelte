<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi6nv12pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi6nv12pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:step-forward" {...props}></Icon>
