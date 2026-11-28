<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td3kli-dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td3kli-dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shovel-solid" {...props}></Icon>
