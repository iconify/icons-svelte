<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_f7byxch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_f7byxch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:small-long-down" {...props}></Icon>
