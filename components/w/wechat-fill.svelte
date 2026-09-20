<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f93lqdbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f93lqdbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wechat-fill" {...props}></Icon>
