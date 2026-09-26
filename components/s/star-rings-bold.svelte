<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebywk9ozr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebywk9ozr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-rings-bold" {...props}></Icon>
