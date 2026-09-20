<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/has-te2vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="has-te2vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:t-shirt-2-fill" {...props}></Icon>
