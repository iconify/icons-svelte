<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct7zfpb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct7zfpb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tubi" {...props}></Icon>
