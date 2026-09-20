<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3i_9n3oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3i_9n3oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:weibo-fill" {...props}></Icon>
