<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq9kh0lwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uq9kh0lwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:snooze-remix" {...props}></Icon>
