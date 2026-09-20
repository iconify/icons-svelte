<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgq83u-6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgq83u-6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:v0-vercel" {...props}></Icon>
