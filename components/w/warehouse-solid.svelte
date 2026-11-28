<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuls9dqno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuls9dqno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:warehouse-solid" {...props}></Icon>
