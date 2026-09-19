<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5_goqbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c5_goqbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:webstorm" {...props}></Icon>
