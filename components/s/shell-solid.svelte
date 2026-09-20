<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv9-thb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qv9-thb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shell-solid" {...props}></Icon>
