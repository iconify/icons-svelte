<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcxkckbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vcxkckbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:thumbtack-solid" {...props}></Icon>
