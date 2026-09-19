<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7bj9actc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7bj9actc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wheelchair-1" {...props}></Icon>
