<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyv38rbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyv38rbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vine" {...props}></Icon>
