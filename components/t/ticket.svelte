<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu7er63ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu7er63ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:ticket" {...props}></Icon>
