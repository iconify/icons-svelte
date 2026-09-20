<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya2vbuq6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya2vbuq6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sleep-fill" {...props}></Icon>
