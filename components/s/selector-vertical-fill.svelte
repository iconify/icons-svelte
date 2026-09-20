<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k95358occ.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k95358occ"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:selector-vertical-fill" {...props}></Icon>
