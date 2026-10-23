<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exa5lfb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exa5lfb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tube-lotion" {...props}></Icon>
