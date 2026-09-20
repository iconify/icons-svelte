<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5n5thbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5n5thbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:send" {...props}></Icon>
