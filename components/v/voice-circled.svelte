<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsgj5pbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsgj5pbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:voice-circled" {...props}></Icon>
