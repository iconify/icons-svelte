<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqc7ymbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqc7ymbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:strawberry-solid" {...props}></Icon>
