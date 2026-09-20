<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i72sl-qwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i72sl-qwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:user" {...props}></Icon>
