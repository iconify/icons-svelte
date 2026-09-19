<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpzcf90uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kpzcf90uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vaadin" {...props}></Icon>
