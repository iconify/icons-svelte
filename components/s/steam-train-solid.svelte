<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-yr89biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-yr89biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:steam-train-solid" {...props}></Icon>
