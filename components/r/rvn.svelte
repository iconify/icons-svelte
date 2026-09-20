<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iefj8go1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iefj8go1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rvn" {...props}></Icon>
