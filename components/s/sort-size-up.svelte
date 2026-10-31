<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y08iq0bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y08iq0bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:sort-size-up" {...props}></Icon>
