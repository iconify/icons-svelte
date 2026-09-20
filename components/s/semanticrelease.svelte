<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg8zgzfkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg8zgzfkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:semanticrelease" {...props}></Icon>
