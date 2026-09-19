<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er43i9stk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er43i9stk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rss" {...props}></Icon>
