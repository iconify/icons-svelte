<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/becfcjx9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="becfcjx9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:train" {...props}></Icon>
