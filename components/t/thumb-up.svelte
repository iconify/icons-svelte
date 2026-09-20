<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge5bx9bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge5bx9bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:thumb-up" {...props}></Icon>
