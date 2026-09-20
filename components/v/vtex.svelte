<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6360bb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6360bb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vtex" {...props}></Icon>
