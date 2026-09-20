<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylh9a2_wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylh9a2_wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:user-question-bold" {...props}></Icon>
