<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvj171rdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvj171rdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:shell" {...props}></Icon>
