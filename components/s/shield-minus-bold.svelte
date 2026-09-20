<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh--6bbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sh--6bbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minus-bold" {...props}></Icon>
