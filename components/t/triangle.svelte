<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi6vm4w9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi6vm4w9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle" {...props}></Icon>
