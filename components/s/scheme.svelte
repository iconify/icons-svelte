<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie6ox79cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":350,"height":512};
const content = `<path class="ie6ox79cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:scheme" {...props}></Icon>
