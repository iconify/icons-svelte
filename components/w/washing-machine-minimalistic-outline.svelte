<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9kdzcatb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9kdzcatb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:washing-machine-minimalistic-outline" {...props}></Icon>
