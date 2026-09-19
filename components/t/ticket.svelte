<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4sh_8-va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4sh_8-va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:ticket" {...props}></Icon>
