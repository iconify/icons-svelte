<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9naz0aiw.css';
import '../../css/z/zh4vk3tqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9naz0aiw"/><path class="zh4vk3tqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:security-key-enforcement" {...props}></Icon>
