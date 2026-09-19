<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvmytbbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvmytbbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:tickets" {...props}></Icon>
