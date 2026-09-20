<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqw92ubzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqw92ubzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-dashed-text" {...props}></Icon>
