<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v380h1daw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v380h1daw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yaml" {...props}></Icon>
