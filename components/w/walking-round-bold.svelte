<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhgzc94rg.css';
import '../../css/n/nr1pzgbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhgzc94rg"/><path clip-rule="evenodd" class="nr1pzgbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:walking-round-bold" {...props}></Icon>
