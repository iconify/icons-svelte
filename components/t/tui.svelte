<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo3hx7b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo3hx7b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tui" {...props}></Icon>
