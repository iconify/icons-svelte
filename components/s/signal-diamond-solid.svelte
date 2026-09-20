<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxfconbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxfconbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:signal-diamond-solid" {...props}></Icon>
