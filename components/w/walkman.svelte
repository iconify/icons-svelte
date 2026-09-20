<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8dd5vb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8dd5vb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:walkman" {...props}></Icon>
