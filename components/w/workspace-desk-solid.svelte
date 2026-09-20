<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9sz-d4qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z9sz-d4qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:workspace-desk-solid" {...props}></Icon>
