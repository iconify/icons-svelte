<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhydsjz3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhydsjz3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:toy-brick" {...props}></Icon>
