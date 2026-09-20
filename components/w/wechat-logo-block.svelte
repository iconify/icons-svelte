<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx-a_8bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hx-a_8bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wechat-logo-block" {...props}></Icon>
