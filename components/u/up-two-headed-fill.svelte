<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-ejmmm0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-ejmmm0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:up-two-headed-fill" {...props}></Icon>
