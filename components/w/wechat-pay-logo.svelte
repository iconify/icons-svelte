<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5q-9mbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5q-9mbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:wechat-pay-logo" {...props}></Icon>
