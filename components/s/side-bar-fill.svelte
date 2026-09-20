<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3gd2abci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3gd2abci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:side-bar-fill" {...props}></Icon>
