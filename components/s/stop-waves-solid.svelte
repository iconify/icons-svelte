<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-lo7wsxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-lo7wsxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:stop-waves-solid" {...props}></Icon>
