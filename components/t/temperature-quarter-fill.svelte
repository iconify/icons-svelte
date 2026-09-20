<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsbym-9ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsbym-9ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:temperature-quarter-fill" {...props}></Icon>
