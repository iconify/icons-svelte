<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh048ubrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh048ubrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-sort-vertical-bold" {...props}></Icon>
