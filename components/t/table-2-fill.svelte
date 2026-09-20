<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6fzf8b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6fzf8b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:table-2-fill" {...props}></Icon>
