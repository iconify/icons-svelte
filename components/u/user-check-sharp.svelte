<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz5b7sfon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz5b7sfon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:user-check-sharp" {...props}></Icon>
