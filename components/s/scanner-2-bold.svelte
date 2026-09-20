<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya8rgwbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya8rgwbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:scanner-2-bold" {...props}></Icon>
