<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5-kmbhbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5-kmbhbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-5-line" {...props}></Icon>
