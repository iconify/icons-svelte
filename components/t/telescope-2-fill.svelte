<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwxqwobia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wwxqwobia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:telescope-2-fill" {...props}></Icon>
