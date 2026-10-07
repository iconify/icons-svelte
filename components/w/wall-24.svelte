<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0g83cboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0g83cboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:wall-24" {...props}></Icon>
