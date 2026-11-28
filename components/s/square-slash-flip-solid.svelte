<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt1lggbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt1lggbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-slash-flip-solid" {...props}></Icon>
