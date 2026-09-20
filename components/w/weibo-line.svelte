<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bli81z1tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bli81z1tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:weibo-line" {...props}></Icon>
