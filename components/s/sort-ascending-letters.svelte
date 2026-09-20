<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp1on0brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp1on0brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-ascending-letters" {...props}></Icon>
