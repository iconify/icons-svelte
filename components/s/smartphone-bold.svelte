<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct4cg4b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct4cg4b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-bold" {...props}></Icon>
