<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0et9ft_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0et9ft_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:unfold-vertical" {...props}></Icon>
