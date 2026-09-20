<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn0xobb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kn0xobb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:zip-folder-solid" {...props}></Icon>
