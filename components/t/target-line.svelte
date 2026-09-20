<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2dm4v5hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2dm4v5hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:target-line" {...props}></Icon>
