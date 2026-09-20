<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2jqw9bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2jqw9bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tornado2-filled" {...props}></Icon>
