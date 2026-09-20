<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otrev-0be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="otrev-0be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-bold-outline" {...props}></Icon>
