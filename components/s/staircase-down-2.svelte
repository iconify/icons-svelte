<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b288o1b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b288o1b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:staircase-down-2" {...props}></Icon>
