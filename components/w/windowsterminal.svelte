<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bou7yz9xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bou7yz9xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:windowsterminal" {...props}></Icon>
