<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr094tbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr094tbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:youtube" {...props}></Icon>
