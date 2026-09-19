<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6n8k5bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6n8k5bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:underline" {...props}></Icon>
