<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5e7fzb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5e7fzb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-text-outline" {...props}></Icon>
