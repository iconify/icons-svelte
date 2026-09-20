<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8q6hq01f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8q6hq01f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:textalign-justifyright-filled" {...props}></Icon>
