<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgd7xbcxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgd7xbcxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shovel" {...props}></Icon>
