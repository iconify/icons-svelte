<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moj687axr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="moj687axr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:set-backward" {...props}></Icon>
