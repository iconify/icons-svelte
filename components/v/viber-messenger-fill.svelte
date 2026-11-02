<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv46si9ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv46si9ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:viber-messenger-fill" {...props}></Icon>
