<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_yxr0bmx.css';
import '../../css/t/t2eelrkyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_yxr0bmx"/><path class="t2eelrkyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:safety-drown-hand-bold" {...props}></Icon>
