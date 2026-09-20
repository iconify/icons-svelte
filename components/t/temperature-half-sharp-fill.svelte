<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwyq1uxli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwyq1uxli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:temperature-half-sharp-fill" {...props}></Icon>
