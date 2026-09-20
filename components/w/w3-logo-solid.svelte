<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa1ioi0ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa1ioi0ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:w3-logo-solid" {...props}></Icon>
