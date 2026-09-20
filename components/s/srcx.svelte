<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0qmicg8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0qmicg8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:srcx" {...props}></Icon>
