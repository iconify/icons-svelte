<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb8v8tbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nb8v8tbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:skull-fill" {...props}></Icon>
