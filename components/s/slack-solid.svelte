<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ira7vdbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ira7vdbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:slack-solid" {...props}></Icon>
