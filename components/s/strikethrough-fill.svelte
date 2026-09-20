<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdxef9m6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdxef9m6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:strikethrough-fill" {...props}></Icon>
