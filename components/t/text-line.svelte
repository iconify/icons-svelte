<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5cc15eec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5cc15eec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-line" {...props}></Icon>
