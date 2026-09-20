<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjykp9b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjykp9b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:snowman" {...props}></Icon>
