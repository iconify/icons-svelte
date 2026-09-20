<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml1wqlf8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml1wqlf8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-remove-2-fill" {...props}></Icon>
