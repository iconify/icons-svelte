<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekyyun60b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekyyun60b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wand2-filled" {...props}></Icon>
