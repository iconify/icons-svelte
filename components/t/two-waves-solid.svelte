<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6xq9oixl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6xq9oixl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:two-waves-solid" {...props}></Icon>
