<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv_eh8bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rv_eh8bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tower-5-fill" {...props}></Icon>
