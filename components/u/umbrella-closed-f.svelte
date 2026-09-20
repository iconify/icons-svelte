<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsg4ydbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="nsg4ydbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:umbrella-closed-f" {...props}></Icon>
